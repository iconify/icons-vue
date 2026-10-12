<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy5740rad.css';
import '../../css/f/f34cgmbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wy5740rad"/><path class="f34cgmbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-can-20-bold" /></template>
