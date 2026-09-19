<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjxrthbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qjxrthbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suit-heart-fill" /></template>
