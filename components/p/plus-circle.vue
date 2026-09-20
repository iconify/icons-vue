<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml8jy-bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml8jy-bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:plus-circle" /></template>
