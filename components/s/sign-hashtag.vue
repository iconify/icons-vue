<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj9jp9dwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fj9jp9dwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:sign-hashtag" /></template>
