<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-1edmnsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":475,"height":512};
const content = `<path class="o-1edmnsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sketchup-make" /></template>
