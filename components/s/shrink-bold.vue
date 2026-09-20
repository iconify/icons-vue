<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz9mvhbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz9mvhbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shrink-bold" /></template>
