<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vukxr8b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vukxr8b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:notifications-off-sharp" /></template>
