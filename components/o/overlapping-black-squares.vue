<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4n515mhi.css';
import '../../css/m/m174vbcva.css';
import '../../css/d/dpsiiab0r.css';
import '../../css/a/a1rfxfwkw.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/i/imrl5j06w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGi4RFXbnq" class="w4n515mhi"/></defs><path class="m174vbcva"/><use href="#SVGi4RFXbnq"/><g class="dpsiiab0r"><path class="a1rfxfwkw"/><use href="#SVGi4RFXbnq"/></g><g class="kdz4acc8r"><path class="imrl5j06w"/><use href="#SVGi4RFXbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:overlapping-black-squares" /></template>
