<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8m08w1ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-20-filled" /></template>
<style>
.n8m08w1ux {
  fill: currentColor;
  d: path("M9.943 2.59a2 2 0 0 1 2.829 0l.73.731c.3.3.268.743.056 1.02a1.5 1.5 0 0 0 2.1 2.1l.112-.07a.77.77 0 0 1 .908.126l.74.74c.78.781.78 2.049 0 2.83L15.6 11.884l-1.359-1.359a.5.5 0 0 0-.707.707l1.359 1.359l-4.828 4.828a2 2 0 0 1-2.829 0l-.74-.74c-.3-.3-.268-.742-.056-1.02l.07-.097a1.5 1.5 0 0 0-2.17-2.004c-.278.212-.721.244-1.022-.056l-.728-.73a2 2 0 0 1 0-2.829l4.827-4.828l1.35 1.35a.5.5 0 0 0 .707-.707l-1.35-1.35zm1.298 4.936a.5.5 0 0 0-.707.707l1.233 1.233a.5.5 0 0 0 .707-.707z");
}

</style>
