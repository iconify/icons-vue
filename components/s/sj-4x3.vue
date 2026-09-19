<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx93awbad.css';
import '../../css/j/jtbbcksnj.css';
import '../../css/l/lm6pm0b8y.css';
import '../../css/d/d7yc9lfha.css';
import '../../css/k/kz5xdnzet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="wx93awbad"/><path class="jtbbcksnj"/><path class="lm6pm0b8y"/><path class="d7yc9lfha"/><path class="kz5xdnzet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:sj-4x3" /></template>
