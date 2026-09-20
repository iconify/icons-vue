<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se8ownbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se8ownbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pin-fill" /></template>
