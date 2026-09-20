<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-u7z_u-t.css';
import '../../css/l/lgeglqbcu.css';
import '../../css/z/zy6utib6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e-u7z_u-t"/><path class="lgeglqbcu"/><path class="zy6utib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:zeabur-light" /></template>
