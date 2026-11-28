<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi6vm4w9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi6vm4w9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle" /></template>
