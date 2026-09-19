<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clwk0tb5w.css';
import '../../css/j/j9lhe6ghc.css';
import '../../css/k/k8hi8zboy.css';
import '../../css/d/dxz0x_bfe.css';
import '../../css/v/vu70-g91b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="clwk0tb5w"/><path class="j9lhe6ghc"/><g class="k8hi8zboy"><path class="dxz0x_bfe"/><path class="vu70-g91b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vsphere" /></template>
