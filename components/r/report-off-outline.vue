<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekk9rgv2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:report-off-outline" /></template>
<style>
.ekk9rgv2k {
  fill: currentColor;
  d: path("m19.108 16.296l-.758-.746l.65-.65V9.1L14.9 5H9.1l-.65.65l-.708-.72l.931-.93h6.654L20 8.673v6.643zM12.5 9.7V7.385h-1V8.7zm7.923 12.139l-3.473-3.473L15.327 20H8.673L4 15.316V8.673L5.623 7.05L2.161 3.577l.708-.708l18.262 18.262zM9.1 19h5.8l1.342-1.342l-9.9-9.9L5 9.1v5.8zm2.466-2.759q-.182-.181-.182-.433t.182-.434t.434-.182t.434.182t.182.434t-.182.433t-.434.182t-.434-.182m-.274-3.533");
}

</style>
