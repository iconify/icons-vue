<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsq4ukbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-new-right-sharp" /></template>
<style>
.rsq4ukbpq {
  fill: currentColor;
  d: path("m19 23l-1.4-1.4l1.575-1.6H15v-2h4.175L17.6 16.4L19 15l4 4zM3 21V3h18v10.35q-.475-.175-.987-.262T18.975 13q-2.5 0-4.237 1.75T13 19q0 .525.088 1.025t.262.975zm8-4h2v-4h4v-2h-4V7h-2v4H7v2h4z");
}

</style>
