<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn5yx0u5x.css';
import '../../css/j/jj9yknbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="gn5yx0u5x"/><path class="jj9yknbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:trophy" /></template>
