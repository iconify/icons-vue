<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b82tnpazp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b82tnpazp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:needleleaved-tree" /></template>
