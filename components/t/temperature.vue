<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp4oqwbqh.css';
import '../../css/i/iynmzp4ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp4oqwbqh"/><circle class="iynmzp4ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:temperature" /></template>
