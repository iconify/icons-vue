<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0uri6bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0uri6bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-filing" /></template>
