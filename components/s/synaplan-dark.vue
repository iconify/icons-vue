<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjo9zj5kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vjo9zj5kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synaplan-dark" /></template>
