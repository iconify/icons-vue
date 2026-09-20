<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv81c1eak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv81c1eak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-circle-line" /></template>
