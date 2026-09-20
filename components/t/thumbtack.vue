<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2x3ni-gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2x3ni-gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:thumbtack" /></template>
