<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewg-glb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewg-glb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pen-line" /></template>
