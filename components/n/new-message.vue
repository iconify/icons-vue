<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm0lb9bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qm0lb9bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:new-message" /></template>
