<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oveujm7yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oveujm7yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-radio" /></template>
