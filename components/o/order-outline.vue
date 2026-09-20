<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3v08dgfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3v08dgfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-outline" /></template>
