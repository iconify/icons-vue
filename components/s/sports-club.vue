<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7fsz4yye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a7fsz4yye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:sports-club" /></template>
