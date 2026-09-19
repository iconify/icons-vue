<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww3upyb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ww3upyb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:perbyte" /></template>
