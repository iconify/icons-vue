<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4n515mhi.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/r/roldwybhr.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/x/xapf8wbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGi4RFXbnq" class="w4n515mhi"/></defs><g class="n1mjunbsu"><path class="roldwybhr"/><use href="#SVGi4RFXbnq"/></g><g class="kdz4acc8r"><use href="#SVGi4RFXbnq"/><path class="xapf8wbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:overlapping-white-squares" /></template>
