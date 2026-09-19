<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2brcc5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ae2brcc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torso-female" /></template>
