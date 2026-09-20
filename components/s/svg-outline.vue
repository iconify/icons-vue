<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xna70pbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xna70pbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:svg-outline" /></template>
