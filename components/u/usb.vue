<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oplieqirt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:usb" /></template>
<style>
.oplieqirt {
  fill: currentColor;
  d: path("M10.934 20.682q-.434-.434-.434-1.066q0-.468.275-.85q.275-.383.725-.543V15.5h-3q-.69 0-1.153-.462t-.463-1.154v-2.107q-.43-.148-.715-.512q-.285-.363-.285-.88q0-.633.434-1.067t1.066-.434t1.067.434t.433 1.066q0 .518-.284.875q-.285.358-.715.518v2.108q0 .23.192.423t.423.192h3V6.27H10l2-2.655l2 2.654h-1.5V14.5h3q.23 0 .423-.192t.193-.423v-2h-1v-3h3v3h-1v2q0 .69-.463 1.153T15.5 15.5h-3v2.723q.456.154.728.537q.272.382.272.855q0 .633-.434 1.067q-.433.434-1.066.434t-1.066-.434");
}

</style>
