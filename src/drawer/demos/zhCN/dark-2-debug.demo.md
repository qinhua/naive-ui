# Dark Debug 2

```html
<n-button @click="modalActive = !modalActive">Toggle</n-button>
<n-drawer v-model:show="modalActive" width="800">
  <n-table :bordered="false" :single-line="false">
    <n-thead>
      <n-tr>
        <n-th>Abandon</n-th>
        <n-th>Abormal</n-th>
        <n-th>Abolish</n-th>
        <n-th>...</n-th>
        <n-th>It's hard to learn words</n-th>
      </n-tr>
    </n-thead>
    <n-tbody>
      <n-tr>
        <n-td>放弃</n-td>
        <n-td>反常的</n-td>
        <n-td>彻底废除</n-td>
        <n-td>...</n-td>
        <n-td>Damn it! I can't remember those words.</n-td>
      </n-tr>
      <n-tr>
        <n-td>...</n-td>
        <n-td>...</n-td>
        <n-td>...</n-td>
        <n-td>...</n-td>
        <n-td>...</n-td>
      </n-tr>
    </n-tbody>
  </n-table>
  <n-list>
    <template #header> hhh </template>
    <template #footer> fff </template>
    <n-list-item>
      <template #prefix>
        <n-button>Prefix</n-button>
      </template>
      <template #suffix>
        <n-button>Suffix</n-button>
      </template>
      <n-thing title="Thing" title-extra="extra" description="description">
        Biu<br />
        Biu<br />
        Biu<br />
      </n-thing>
    </n-list-item>
    <n-list-item>
      <n-thing title="Thing" title-extra="extra" description="description">
        Biu<br />
        Biu<br />
        Biu<br />
      </n-thing>
      <template #suffix>
        <n-button>Suffix</n-button>
      </template>
    </n-list-item>
  </n-list>
  <n-list bordered>
    <template #header> hhh </template>
    <template #footer> fff </template>
    <n-list-item>
      <template #prefix>
        <n-button>Prefix</n-button>
      </template>
      <template #suffix>
        <n-button>Suffix</n-button>
      </template>
      <n-thing title="Thing" title-extra="extra" description="description">
        Biu<br />
        Biu<br />
        Biu<br />
      </n-thing>
    </n-list-item>
    <n-list-item>
      <n-thing title="Thing" title-extra="extra" description="description">
        Biu<br />
        Biu<br />
        Biu<br />
      </n-thing>
      <template #suffix>
        <n-button>Suffix</n-button>
      </template>
    </n-list-item>
  </n-list>
  <n-descriptions bordered>
    <n-descriptions-item>
      <template #label> Breakfast </template>
      Apple
    </n-descriptions-item>
    <n-descriptions-item label="Lunch"> Apple </n-descriptions-item>
    <n-descriptions-item label="Supper"> Apple </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
  </n-descriptions>
  <n-descriptions label-placement="left" bordered>
    <n-descriptions-item>
      <template #label> Breakfast </template>
      Apple
    </n-descriptions-item>
    <n-descriptions-item label="Lunch"> Apple </n-descriptions-item>
    <n-descriptions-item label="Supper"> Apple </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
  </n-descriptions>
  <n-descriptions>
    <n-descriptions-item>
      <template #label> Breakfast </template>
      Apple
    </n-descriptions-item>
    <n-descriptions-item label="Lunch"> Apple </n-descriptions-item>
    <n-descriptions-item label="Supper"> Apple </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
  </n-descriptions>
  <n-descriptions label-placement="left">
    <n-descriptions-item>
      <template #label> Breakfast </template>
      Apple
    </n-descriptions-item>
    <n-descriptions-item label="Lunch"> Apple </n-descriptions-item>
    <n-descriptions-item label="Supper"> Apple </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
    <n-descriptions-item label="Why Long">
      Why <br />
      Long <br />
      Long <br />
      Long <br />
      Long <br />
      Long
    </n-descriptions-item>
  </n-descriptions>
</n-drawer>
```

```js
export default {
  data () {
    return {
      modalActive: false
    }
  }
}
```