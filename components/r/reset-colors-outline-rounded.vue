<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydfq9b2dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-colors-outline-rounded" /></template>
<style>
.ydfq9b2dd {
  fill: currentColor;
  d: path("M16.912 21.936q-.18-.065-.327-.213l-3.789-3.788q-.148-.148-.222-.327t-.074-.358t.074-.36t.222-.33l3.766-3.76l-1.5-1.48q-.146-.147-.146-.355q0-.207.146-.353t.356-.146t.357.146l5.973 5.948q.148.148.213.327q.064.179.064.357t-.064.36q-.065.183-.213.33l-3.788 3.789q-.148.148-.33.213q-.182.064-.36.064t-.359-.065M13.7 17.04h7.08l-3.53-3.531zM12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15.5q0-.213.143-.357T9.5 15t.357.143t.143.357v3.692q0 .349-.23.578t-.578.23H5.5q-.213 0-.357-.143T5 19.5t.143-.357T5.5 19h2.812q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.562 0 4.562 1.418t2.884 3.688q.073.188 0 .38q-.073.193-.261.266q-.189.073-.384-.01t-.268-.27q-.756-1.97-2.513-3.221T12 5");
}

</style>
