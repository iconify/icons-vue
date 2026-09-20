<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stvuidp4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="stvuidp4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:twitter-square" /></template>
