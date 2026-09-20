<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp06w2bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tilt-arrow-down-outline" /></template>
<style>
.mp06w2bge {
  fill: currentColor;
  d: path("M6.616 20q-.691 0-1.153-.462T5 18.384V5.616q0-.691.463-1.153T6.616 4h10.788q.69 0 1.153.463t.462 1.153v12.769q0 .69-.462 1.153T17.404 20zm0-1h10.788q.269 0 .442-.173t.173-.442V5.615q0-.269-.173-.442T17.404 5H6.616q-.27 0-.452.173q-.183.173-.183.443v12.769q0 .269.183.442q.182.173.452.173m4.903-5.536L9.4 11.35l-.708.708l3.327 3.327l3.289-3.289l-.708-.713l-2.08 2.08V8.77h-1zM17.404 19H5.98h12.038z");
}

</style>
