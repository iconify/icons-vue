<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5ay8d92v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:solo-dining-sharp" /></template>
<style>
.i5ay8d92v {
  fill: currentColor;
  d: path("M9.73 7.789q-1 0-1.701-.702t-.702-1.702q0-.981.702-1.693q.702-.711 1.702-.711q.98 0 1.692.711t.712 1.693q0 1-.712 1.702t-1.692.702M2 21v-1h2v-7.471q0-.587.559-1.183q.558-.596 1.524-1.019q.8-.363 1.757-.566q.958-.203 1.89-.203q.928 0 1.913.215q.986.216 1.803.604q.948.442 1.472 1.007q.524.564.524 1.145v1.317h-4.998L12.021 20h2.46l-.962-3.77h8.347L20.923 20H22v1z");
}

</style>
