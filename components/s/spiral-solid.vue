<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3-c1ibyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3-c1ibyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spiral-solid" /></template>
