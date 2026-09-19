<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kinzzobxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":718,"height":669};
const content = `<path class="kinzzobxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:user" /></template>
