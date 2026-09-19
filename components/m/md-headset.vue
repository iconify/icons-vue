<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j--st9bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j--st9bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-headset" /></template>
