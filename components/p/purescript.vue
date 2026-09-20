<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np5n44mha.css';
import '../../css/j/j5tmw1bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="np5n44mha"/><path class="j5tmw1bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:purescript" /></template>
