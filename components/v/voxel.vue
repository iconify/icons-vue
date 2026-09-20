<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed58ot-_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed58ot-_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:voxel" /></template>
