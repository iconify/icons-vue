<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2fosdizo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2fosdizo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smiley-sad-1-bold" /></template>
