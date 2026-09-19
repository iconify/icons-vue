<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv6imwvyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zv6imwvyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:typing" /></template>
