<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1xdd0bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="f1xdd0bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-gitlab" /></template>
