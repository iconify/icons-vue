<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlpntabar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-cinematic-blur-sharp" /></template>
<style>
.dlpntabar {
  fill: currentColor;
  d: path("M13.27 21v-6.638h.709l.56 1.138h1.269l-.635-1.27h1.27l.634 1.27h1.27l-.636-1.27h1.27l.634 1.27h1.27l-.635-1.27h1.48V21zm-3.136 0l-.361-2.892q-.479-.145-1.035-.454q-.557-.31-.948-.664l-2.667 1.135l-1.865-3.25l2.306-1.739q-.045-.27-.073-.558q-.03-.288-.03-.559q0-.252.03-.53q.028-.278.073-.626L3.258 9.126l1.865-3.212L7.771 7.03q.448-.373.97-.673q.52-.3 1.013-.464L10.134 3h3.732l.361 2.912q.575.202 1.016.463t.909.654l2.725-1.115l1.865 3.211l-2.382 1.796q.082.31.092.569t.01.51h-3.989q0-1.046-.727-1.773T11.973 9.5t-1.773.727T9.473 12q0 .796.416 1.408q.415.611 1.111.904V21z");
}

</style>
