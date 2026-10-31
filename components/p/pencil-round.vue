<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1jb7dbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1jb7dbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-round" /></template>
