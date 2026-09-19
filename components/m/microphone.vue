<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bac56-jdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1664};
const content = `<path class="bac56-jdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:microphone" /></template>
