<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd7ar58ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nd7ar58ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:play-square-f" /></template>
