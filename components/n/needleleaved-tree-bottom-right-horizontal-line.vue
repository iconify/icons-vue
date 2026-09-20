<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b82tnpazp.css';
import '../../css/v/v75yc8b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b82tnpazp"/><path class="v75yc8b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:needleleaved-tree-bottom-right-horizontal-line" /></template>
