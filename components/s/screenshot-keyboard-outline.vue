<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6v2_xj9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-keyboard-outline" /></template>
<style>
.j6v2_xj9h {
  fill: currentColor;
  d: path("M12 14.5q-1.036 0-1.768-.732T9.5 12t.732-1.768T12 9.5t1.768.732T14.5 12t-.732 1.768T12 14.5m2.479-.021Q15.5 13.458 15.5 12t-1.021-2.479T12 8.5T9.521 9.521T8.5 12t1.021 2.479T12 15.5t2.479-1.021M4.616 19q-.691 0-1.154-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
