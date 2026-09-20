<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig32bu-lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-add-sharp" /></template>
<style>
.ig32bu-lb {
  fill: currentColor;
  d: path("M6.993 20v-4H3.577V8.616h16.846v2.807q-.306-.107-.642-.17q-.335-.06-.667-.06q-1.7 0-3.115.878q-1.415.879-2.172 2.39H8V19h5.466q.078.28.203.521q.125.24.264.479zM7 7.846v-3.23h10v3.23zm11.596 12.75v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
