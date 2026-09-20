<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-fdvzb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:share-eta-sharp" /></template>
<style>
.o-fdvzb5b {
  fill: currentColor;
  d: path("M10.025 24q-2.075 0-3.9-.788t-3.187-2.15t-2.15-3.187T0 14q0-2.075.788-3.9t2.15-3.187t3.187-2.15t3.9-.788q.25 0 .488.013t.487.037v2q-.25-.025-.488-.038t-.487-.012q-3.35 0-5.687 2.338T2 14q0 3.325 2.338 5.663T10.025 22q3.325 0 5.663-2.337T18.025 14h2q0 2.05-.787 3.875t-2.15 3.188t-3.175 2.15t-3.888.787m3.275-5.3L9 14.4V9h2v4.6l3.7 3.7zm8.55-6.7q-.575-3.55-3-6.163T13 2.35V.3q4.275.925 7.263 4.125T23.874 12zm-4.075 0q-.475-1.875-1.737-3.3T13 6.55V4.425q2.575.8 4.425 2.838t2.4 4.737z");
}

</style>
