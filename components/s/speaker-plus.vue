<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjxj6dbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjxj6dbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:speaker-plus" /></template>
