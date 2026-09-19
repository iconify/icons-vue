<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzhby49lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hzhby49lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vest" /></template>
