<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzxxbb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-rounded" /></template>
<style>
.xfzxxbb4m {
  fill: currentColor;
  d: path("M6.451 20.857q-.143-.143-.143-.357v-4.27H3.787q-.46 0-.696-.384q-.237-.384-.02-.788l1.352-2.689V9.385H3.5q-.213 0-.357-.144T3 8.885t.143-.357q.144-.144.357-.144h6.616q.213 0 .356.144q.144.143.144.357q0 .213-.144.356q-.143.144-.356.144h-.924v2.984l1.352 2.689q.218.404-.019.788q-.236.385-.696.385H7.308V20.5q0 .214-.143.357T6.808 21t-.357-.143M19.385 19h-6.443q-.213 0-.356-.143t-.144-.357t.144-.357t.356-.143h6.443q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T19.385 6H3.5q-.213 0-.357-.143T3 5.5t.143-.357T3.5 5h15.885q.69 0 1.153.463T21 6.616v10.769q0 .69-.462 1.153T19.385 19");
}

</style>
