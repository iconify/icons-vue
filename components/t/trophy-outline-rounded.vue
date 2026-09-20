<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ups4kmbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trophy-outline-rounded" /></template>
<style>
.ups4kmbfy {
  fill: currentColor;
  d: path("M11.5 19v-3.754q-1.379-.102-2.399-.999t-1.278-2.258q-1.587-.187-2.705-1.301T4 8v-.385q0-.67.472-1.143Q4.944 6 5.616 6h2.038v-.385q0-.67.472-1.143Q8.598 4 9.269 4h5.462q.671 0 1.143.472t.472 1.143V6h2.039q.67 0 1.143.472q.472.472.472 1.144V8q0 1.573-1.118 2.688t-2.705 1.3q-.258 1.362-1.278 2.259t-2.399 1V19h2.616q.213 0 .356.143q.144.143.144.357t-.144.357t-.356.143H8.885q-.214 0-.357-.143q-.144-.143-.144-.357t.144-.357t.357-.143zm-3.846-8.084V7H5.615q-.269 0-.442.173T5 7.616V8q0 1.123.762 1.953q.761.83 1.892.963m6.692 2.392q.962-.962.962-2.346V5.616q0-.27-.174-.443Q14.962 5 14.692 5H9.308q-.27 0-.442.173q-.174.173-.174.443v5.346q0 1.384.962 2.346q.962.961 2.346.961t2.346-.961m2-2.393q1.131-.132 1.893-.962Q19 9.123 19 8v-.385q0-.269-.173-.442T18.385 7h-2.039zM12 9.635");
}

</style>
