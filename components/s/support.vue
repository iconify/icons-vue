<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/a/agd2mgb0r.css';
import '../../css/x/xp8nmbbsz.css';
import '../../css/j/jxdco9bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><circle class="agd2mgb0r"/><circle class="xp8nmbbsz"/><path class="jxdco9bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:support" /></template>
