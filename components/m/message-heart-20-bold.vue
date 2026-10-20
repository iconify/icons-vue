<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxvbik02p.css';
import '../../css/m/m6b4vpcmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvbik02p"/><path class="m6b4vpcmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-heart-20-bold" /></template>
