<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb4ztpb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb4ztpb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pbr" /></template>
