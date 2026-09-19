<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi07aqbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zi07aqbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xp" /></template>
