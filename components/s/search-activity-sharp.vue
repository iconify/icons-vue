<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eplgxmbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:search-activity-sharp" /></template>
<style>
.eplgxmbja {
  fill: currentColor;
  d: path("M14.401 4.867q-.228-.229-.228-.56t.229-.56t.56-.228t.56.23t.228.56t-.229.56t-.56.227t-.56-.229m-.058 15.385q-.228-.23-.228-.56q0-.332.23-.56q.228-.228.56-.228t.56.229t.227.56q0 .332-.229.56q-.228.228-.56.228t-.56-.23m4-12.115q-.227-.229-.227-.56t.228-.56t.561-.228t.56.23q.227.228.227.56t-.229.56t-.56.227t-.56-.229m-.057 8.904q-.228-.229-.228-.56t.229-.56t.56-.228t.56.23t.228.56t-.23.56q-.228.227-.56.227q-.331 0-.56-.229m1.366-4.48q-.228-.23-.228-.561t.229-.56q.229-.227.56-.227t.56.229t.228.56t-.229.56t-.56.227t-.56-.229M12 21q-1.864 0-3.507-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51q.709-1.643 1.924-2.859T8.49 3.709T12 3v1Q8.65 4 6.325 6.325T4 12t2.325 5.675T12 20zm3.3-5.012l-3.8-3.8V7.5h1v4.312l3.489 3.488z");
}

</style>
