<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh571vzof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh571vzof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:turbo" /></template>
