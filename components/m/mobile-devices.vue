<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbqaj9bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbqaj9bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mobile-devices" /></template>
