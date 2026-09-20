<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qftym_bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qftym_bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voilib-dark" /></template>
