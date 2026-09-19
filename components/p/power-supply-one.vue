<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irxbhzw4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="irxbhzw4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:power-supply-one" /></template>
