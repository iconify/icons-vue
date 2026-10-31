<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w983d8bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w983d8bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-round" /></template>
