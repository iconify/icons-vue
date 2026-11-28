<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkyuc8boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkyuc8boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:passport" /></template>
