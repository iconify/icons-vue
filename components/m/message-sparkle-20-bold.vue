<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxvbik02p.css';
import '../../css/a/adx6enbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvbik02p"/><path class="adx6enbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-sparkle-20-bold" /></template>
