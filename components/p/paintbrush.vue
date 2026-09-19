<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df-lw4b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="df-lw4b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:paintbrush" /></template>
