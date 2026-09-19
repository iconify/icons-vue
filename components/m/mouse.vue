<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x55m2-bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x55m2-bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:mouse" /></template>
