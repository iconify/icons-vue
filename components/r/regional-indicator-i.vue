<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htu6zoakn.css';
import '../../css/i/iz026krfb.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/u/usozxnbrm.css';
import '../../css/z/z299p9xzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="htu6zoakn"/><path class="iz026krfb"/><g class="kdz4acc8r"><circle class="usozxnbrm"/><path class="z299p9xzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:regional-indicator-i" /></template>
