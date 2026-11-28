<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-36qhzvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-36qhzvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:music-note-heart" /></template>
