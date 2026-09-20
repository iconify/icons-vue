<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkr45ebwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qkr45ebwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:spatial" /></template>
