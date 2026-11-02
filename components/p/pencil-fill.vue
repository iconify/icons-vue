<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_uoytyif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_uoytyif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-fill" /></template>
