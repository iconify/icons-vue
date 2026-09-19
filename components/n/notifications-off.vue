<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8ovz0q5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8ovz0q5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:notifications-off" /></template>
