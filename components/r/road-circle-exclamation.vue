<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84do1r9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="w84do1r9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:road-circle-exclamation" /></template>
