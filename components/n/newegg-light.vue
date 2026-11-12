<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqle04bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqle04bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newegg-light" /></template>
