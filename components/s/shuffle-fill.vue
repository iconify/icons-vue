<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwxf3bbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwxf3bbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shuffle-fill" /></template>
