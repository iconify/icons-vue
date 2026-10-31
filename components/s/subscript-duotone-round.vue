<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c19_p2b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c19_p2b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subscript-duotone-round" /></template>
