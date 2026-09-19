<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxqrty3pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxqrty3pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:playlist-shuffle-light" /></template>
