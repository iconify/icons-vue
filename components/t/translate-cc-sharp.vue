<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df2ig4cpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:translate-cc-sharp" /></template>
<style>
.df2ig4cpc {
  fill: currentColor;
  d: path("m3.73 18.308l-.613-.647l2.94-2.852q-.545-.665-1.019-1.361T4.16 12h.981q.331.579.698 1.117t.816 1.056q.742-.842 1.342-1.765t.956-1.985H2v-.885h4.23V8.231h.885v1.307h4.624v.885H9.858q-.406 1.235-1.084 2.315q-.678 1.081-1.537 2.066q.369.425.812.862t.851.807l-.344.89q-.464-.419-.971-.914q-.508-.495-.95-.988zm4.299 4.23l3.433-8.769h.932l3.452 8.77h-.954l-.92-2.416H9.903l-.935 2.415zm2.177-3.196h3.463l-1.735-4.511zm5.236-9.265h3.885V8.616h-.885v.576h-2.115V5.577h2.115v.615h.885v-1.5h-3.885zM22 12.769h-9.02V8.654h-2.268V5.577h2.115v.615h.885v-1.5H9.827v3.962H8.134V6.98h-1V2H22z");
}

</style>
