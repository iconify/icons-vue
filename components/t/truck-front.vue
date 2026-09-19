<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffgls6dgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffgls6dgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:truck-front" /></template>
