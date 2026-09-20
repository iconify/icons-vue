<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f200fw0ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f200fw0ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:noun-project" /></template>
