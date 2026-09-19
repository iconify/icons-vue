<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgh8nu16y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wgh8nu16y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pause-sharp" /></template>
