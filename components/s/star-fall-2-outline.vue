<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb3o8uw0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb3o8uw0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-2-outline" /></template>
