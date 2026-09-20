<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vljrjmbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-unread-outline" /></template>
<style>
.vljrjmbqa {
  fill: currentColor;
  d: path("m6.808 21l-.5-.5v-4.27H3v-1l1.423-2.86V9.384H3v-1h7.616v1H9.192v2.984l1.424 2.862v1H7.308v4.27zm-2.662-5.77H9.47l-1.278-2.54V9.385H5.423v3.304zm11.585-7.96Q15 6.538 15 5.5t.73-1.77T17.5 3t1.77.73T20 5.5t-.73 1.77T17.5 8t-1.77-.73M13.043 6H3q0-.402.299-.701T4 5h9.042q-.011.116-.026.238q-.016.12-.016.242q0 .14.016.262q.015.122.026.257m6.343 13h-6.943v-1h6.943q.269 0 .442-.173t.173-.442V9.21q.292-.18.542-.387T21 8.346v9.039q0 .69-.462 1.153T19.385 19");
}

</style>
