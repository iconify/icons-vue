<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py9rf3d8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py9rf3d8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:text-image-left" /></template>
