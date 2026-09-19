<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd9dtcckh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sd9dtcckh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:push" /></template>
