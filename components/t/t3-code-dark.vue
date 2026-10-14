<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmf9fexod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tmf9fexod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t3-code-dark" /></template>
