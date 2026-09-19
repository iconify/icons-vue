<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xna4wac8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":382,"height":512};
const content = `<path class="xna4wac8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:q" /></template>
