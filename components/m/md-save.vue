<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl1mrtb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rl1mrtb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-save" /></template>
