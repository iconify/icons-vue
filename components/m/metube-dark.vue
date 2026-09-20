<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdt0oujpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdt0oujpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metube-dark" /></template>
