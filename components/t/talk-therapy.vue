<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gibmf8bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:talk-therapy" /></template>
<style>
.gibmf8bue {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 1.75H5q-1.139 0-1.945.805q-.805.806-.805 1.945V7q0 2.622 2.5 2.744V11.5q0 .132.045.255q.045.124.129.225q.047.057.105.103q.057.047.122.081q.066.034.137.055t.144.028q.074.007.147-.001q.074-.008.144-.03q.071-.022.136-.057q.064-.036.121-.083L8.772 9.75H13q2.75 0 2.75-2.75V4.5q0-2.75-2.75-2.75m-1 9.5h7q2.75 0 2.75 2.75v2.5q0 2.622-2.5 2.744V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.132 0-.255-.045q-.124-.045-.225-.129l-2.792-2.326H12q-2.75 0-2.75-2.75V14q0-2.75 2.75-2.75");
}

</style>
