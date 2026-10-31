<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c99xlfb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c99xlfb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-round" /></template>
