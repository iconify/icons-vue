<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3-hujoeb.css';
import '../../css/w/w5cu6gb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3-hujoeb"/><path class="w5cu6gb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:receipt" /></template>
