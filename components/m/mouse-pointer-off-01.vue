<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md09hy4px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md09hy4px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-pointer-off-01" /></template>
