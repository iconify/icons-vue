<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdb2gpbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wdb2gpbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:smiling-face-with-eyeglasses-in-circle-outline" /></template>
