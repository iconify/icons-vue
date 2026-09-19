<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="psy0_5b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:plus" /></template>
<style>
.psy0_5b0f {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M38 26V2H26v24H2v12h24v24h12V38h24V26z");
}

</style>
