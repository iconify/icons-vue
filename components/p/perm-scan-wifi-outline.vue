<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdco038lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-scan-wifi-outline" /></template>
<style>
.qdco038lk {
  fill: currentColor;
  d: path("M12 21L0 9q2.375-2.425 5.488-3.713T12 4t6.513 1.288T24 9zm0-2.85l9.1-9.1q-1.975-1.5-4.3-2.275T12 6t-4.8.775T2.9 9.05zM11 15h2v-5h-2zm1.713-6.288Q13 8.425 13 8t-.288-.712T12 7t-.712.288T11 8t.288.713T12 9t.713-.288M12 18.15");
}

</style>
