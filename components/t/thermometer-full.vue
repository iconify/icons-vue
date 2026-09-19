<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4jnmdp6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="r4jnmdp6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thermometer-full" /></template>
