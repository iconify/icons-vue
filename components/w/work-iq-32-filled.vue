<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f0zryvb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-32-filled" /></template>
<style>
.f0zryvb2f {
  fill: currentColor;
  d: path("M21.735 5.699a2.5 2.5 0 0 1 2.52.005l2.522 1.48A4.5 4.5 0 0 1 29 11.067v7.69a6.97 6.97 0 0 0-4-1.257a6.99 6.99 0 0 0-5.5 2.672V20a2.5 2.5 0 0 0-5 0v9c0 .466.13.9.352 1.274a4.5 4.5 0 0 1-1.13-.47l-2.488-1.46A2.5 2.5 0 0 1 10 26.187V13.95c0-.891.475-1.715 1.245-2.163zM17 19a1 1 0 0 1 1 1v9a1 1 0 0 1-2 0v-9a1 1 0 0 1 1-1m8 0a5.5 5.5 0 0 1 4.53 8.617l.677.676a1 1 0 0 1-1.414 1.414l-.677-.676A5.5 5.5 0 1 1 25 19m0 2a3.5 3.5 0 1 0 1.664 6.578l-1.371-1.37a1 1 0 0 1 1.414-1.415l1.371 1.372A3.5 3.5 0 0 0 25 21M13.732 2.164a4.5 4.5 0 0 1 4.536 0l2.796 1.631q-.169.08-.333.174l-10.49 6.09A4.5 4.5 0 0 0 8 13.95v12.236q0 .155.01.31l-2.778-1.62A4.5 4.5 0 0 1 3 20.988V11.01c0-1.6.85-3.081 2.232-3.888z");
}

</style>
