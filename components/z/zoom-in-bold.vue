<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg3_1fb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg3_1fb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:zoom-in-bold" /></template>
