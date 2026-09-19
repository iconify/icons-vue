<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0yrwnhfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0yrwnhfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-jet" /></template>
