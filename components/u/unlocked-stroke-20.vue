<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fel8-rbzx.css';
import '../../css/q/qtj15rupr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fel8-rbzx"/><path class="qtj15rupr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:unlocked-stroke-20" /></template>
