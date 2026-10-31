<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziucbk6ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziucbk6ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spotify-round" /></template>
