<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw71cpb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw71cpb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:music-fill" /></template>
