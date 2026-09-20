<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae849gbxa.css';
import '../../css/k/kz60qjbkb.css';
import '../../css/n/nuer4ybvc.css';
import '../../css/u/u6w5clbyu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/g/ggvrgk83l.css';
import '../../css/c/cu2qjub5t.css';
import '../../css/t/tahp7wbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ae849gbxa"><path class="kz60qjbkb"/><path class="nuer4ybvc"/><circle class="u6w5clbyu"/></g><g class="ij2x_72vy"><path class="ggvrgk83l"/><path class="cu2qjub5t"/><circle class="tahp7wbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:warning" /></template>
