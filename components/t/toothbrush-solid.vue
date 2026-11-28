<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irl3n7ied.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irl3n7ied"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:toothbrush-solid" /></template>
