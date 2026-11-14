<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4il2lbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:staff-training" /></template>
<style>
.l4il2lbnl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.181 8.821l8.5-4q.151-.071.319-.071t.319.071l8.5 4q.097.046.177.116t.137.161t.087.193t.03.209V15q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T19.75 15v-4.318l-2.01.946q.01.06.01.122V16q0 .149-.057.287t-.163.243q-2.219 2.22-5.53 2.22t-5.53-2.22q-.106-.105-.163-.243T6.25 16v-4.25q0-.062.01-.122l-3.079-1.449q-.135-.064-.236-.174q-.1-.111-.151-.251t-.043-.289t.07-.284q.056-.119.149-.211q.092-.093.211-.149m9.138 5.358q-.151.071-.319.071t-.319-.071l-3.931-1.85v3.35Q9.474 17.25 12 17.25t4.25-1.571v-3.35z");
}

</style>
