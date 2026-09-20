<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxtr1katy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxtr1katy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:spiral-shape-solid" /></template>
