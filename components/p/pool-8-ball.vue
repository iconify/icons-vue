<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zelne8bhe.css';
import '../../css/k/ke20lckrt.css';
import '../../css/j/j53dyo7_r.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/s/s6wo44j_t.css';
import '../../css/l/l6nsbxbxq.css';
import '../../css/p/poeq14etq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="zelne8bhe"/><circle class="ke20lckrt"/><path class="j53dyo7_r"/><g class="ij2x_72vy"><circle class="s6wo44j_t"/><circle class="l6nsbxbxq"/><circle class="poeq14etq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pool-8-ball" /></template>
