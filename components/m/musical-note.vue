<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdxhmdboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdxhmdboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:musical-note" /></template>
