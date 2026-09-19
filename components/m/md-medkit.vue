<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvd52nqvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvd52nqvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-medkit" /></template>
