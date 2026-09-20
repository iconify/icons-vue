<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gszf4yboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gszf4yboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raspberry-pi-dark" /></template>
