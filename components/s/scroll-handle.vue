<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0tqoiufg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l0tqoiufg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:scroll-handle" /></template>
