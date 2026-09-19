<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb4-vf7ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="fb4-vf7ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wordpress" /></template>
