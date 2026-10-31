<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo4h3mbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo4h3mbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-fill-round" /></template>
