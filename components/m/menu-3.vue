<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c41m9pbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c41m9pbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:menu-3" /></template>
