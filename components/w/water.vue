<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8rjzwzya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l8rjzwzya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:water" /></template>
