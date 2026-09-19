<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me1not0hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="me1not0hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pied-piper" /></template>
