<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9vy3s1jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v9vy3s1jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:vine-with-circle" /></template>
