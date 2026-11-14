<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr8yyrpjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:segmented-mirror" /></template>
<style>
.fr8yyrpjx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.141 3.051l2.749 1.618Q17 5.321 17 6.608v3.284q0 .238-.038.454q.215.078.429.205h.001l2.749 1.618q1.109.652 1.109 1.939v3.284q0 1.287-1.109 1.939l-2.75 1.618q-1.141.672-2.283 0l-2.749-1.618q-.197-.115-.359-.251q-.162.135-.359.251l-2.75 1.618q-1.141.672-2.282 0l-2.75-1.618q-1.109-.652-1.109-1.939v-3.284q0-1.287 1.108-1.939l2.751-1.618q.214-.127.429-.206Q7 10.129 7 9.892V6.608q0-1.287 1.109-1.939l2.75-1.618q1.141-.672 2.282 0");
}

</style>
