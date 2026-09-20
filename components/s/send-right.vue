<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1acvi-ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1acvi-ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:send-right" /></template>
