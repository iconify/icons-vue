<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osqz-p07j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="osqz-p07j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:menu-left" /></template>
