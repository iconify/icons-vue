<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1my92dum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-photography-outline-sharp" /></template>
<style>
.j1my92dum {
  fill: currentColor;
  d: path("m21 18.183l-1-1V7h-4.011l-1.843-2h-4.29l-.97 1.07l-.713-.714L9.423 4h5.154l1.85 2H21zM3 20V6h3.006l1 1H4v12h15.006l1 1zm12.092-4.913q-.51.754-1.31 1.199T12 16.73q-1.567 0-2.649-1.082T8.269 13q0-.982.445-1.782t1.2-1.31l.719.719q-.618.35-.99.97T9.268 13q0 1.166.783 1.948q.783.783 1.948.783q.782 0 1.402-.373t.971-.99zm-.456-4.723q.478.459.757 1.063q.28.604.318 1.323v.07q0 .034-.005.069l-3.594-3.595q.034-.006.069-.006h.069q.72.039 1.323.319q.604.28 1.063.757m6.474 12.167L1.887 3.308l.713-.714l19.223 19.223zm-6.68-10.917");
}

</style>
