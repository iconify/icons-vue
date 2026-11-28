<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zob65uuei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zob65uuei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:playlist-heart" /></template>
