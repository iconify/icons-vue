<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-illub7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-illub7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:science-molecule-strucutre-bold" /></template>
