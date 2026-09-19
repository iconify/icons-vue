<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd-1kf17z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd-1kf17z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:monitor" /></template>
