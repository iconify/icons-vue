<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0kk_sbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z0kk_sbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:play" /></template>
