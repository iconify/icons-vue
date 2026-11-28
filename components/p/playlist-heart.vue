<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef25pac2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef25pac2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:playlist-heart" /></template>
