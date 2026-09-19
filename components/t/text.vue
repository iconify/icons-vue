<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy85v-b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy85v-b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:text" /></template>
