<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kguenkyrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:metro-rounded" /></template>
<style>
.kguenkyrm {
  fill: currentColor;
  d: path("M4 19.077V5.381q0-.57.406-.975T5.386 4h.61q.431 0 .793.248t.505.65L12 17.338L16.65 4.96q.167-.446.55-.702q.38-.258.853-.258h.455q.618 0 1.054.437T20 5.492v13.585q0 .384-.264.654q-.265.269-.659.269t-.659-.27t-.264-.653V6.366l-5.06 13.09q-.086.235-.296.39t-.472.154h-.664q-.262 0-.475-.155t-.3-.39L5.847 6.46v12.617q0 .384-.265.654T4.923 20t-.659-.27T4 19.078");
}

</style>
