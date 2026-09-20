<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x03ow4b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x03ow4b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:office-building-2" /></template>
