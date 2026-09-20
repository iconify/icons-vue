<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnrctobiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sync-desktop-outline-sharp" /></template>
<style>
.mnrctobiv {
  fill: currentColor;
  d: path("M17.9 11q-.175-1.025-.675-1.9T16 7.55V10h-2V4h6v2h-2.725q1.075.95 1.763 2.225T19.925 11zM15 17h5v-2h-5zm-2 2v-6h9v6zm-9 1v-2h2.725q-1.275-1.1-2-2.65T4 12q0-2.8 1.7-4.937T10 4.25v2.1q-1.75.625-2.875 2.163T6 12q0 1.35.538 2.488T8 16.45V14h2v6zm8 2v-2h11v2zm3-5v-2z");
}

</style>
