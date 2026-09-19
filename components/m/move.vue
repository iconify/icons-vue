<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9fd8ybb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="kd9fd8ybb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:move" /></template>
