<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm5kf3b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xm5kf3b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-monopolar" /></template>
