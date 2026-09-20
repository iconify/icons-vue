<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx-94gb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voice-chat-off" /></template>
<style>
.qx-94gb1e {
  fill: currentColor;
  d: path("M20.27 21.685L15.572 17H6.077L3 20.077V4.416L1.008 2.423l.707-.707l19.262 19.261zM16.807 10.5h.884v-1h-.884zm2.892 6.466l-4.508-4.547V7.5h-.884v4.035L12.442 9.65V5.5h-.884v3.246L5.85 3h13.535q.69 0 1.153.463T21 4.615v10.77q0 .65-.363 1.041q-.362.391-.937.54m-7.384-3.235l-.758-.758V14.5h.758zM8.808 12.5h.884v-1.392l-.884-.885zm-2.5-2h.884v-.7l-.3-.3h-.584z");
}

</style>
