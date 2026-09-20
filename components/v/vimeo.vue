<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv4v6pbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4v6pbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vimeo" /></template>
