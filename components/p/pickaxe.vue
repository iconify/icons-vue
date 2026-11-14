<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3f6oebwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pickaxe" /></template>
<style>
.k3f6oebwk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.25q-6.311 0-9.53 3.22q-.077.076-.128.171t-.075.2q-.023.106-.015.213q.008.108.046.209q.052.14.154.249t.238.171t.285.067t.288-.048q2.292-.859 6.487-1.033V20q0 2.25 2.25 2.25T14.25 20V7.669q4.195.174 6.487 1.033q.101.038.209.046t.213-.015t.2-.075t.171-.128q.053-.052.094-.113t.069-.13t.043-.141T21.75 8t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113Q18.311 4.25 12 4.25");
}

</style>
