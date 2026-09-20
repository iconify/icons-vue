<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpmbt0b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-alt-outline-rounded" /></template>
<style>
.bpmbt0b4c {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6zm8.116-1.038h6.076q.349 0 .578-.23t.23-.578v-4.077q0-.348-.23-.578t-.578-.23h-6.076q-.349 0-.578.23t-.23.578v4.077q0 .348.23.578t.578.23m.192-1v-3.693H18v3.692z");
}

</style>
