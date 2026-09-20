<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azgrjsb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azgrjsb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pico-sh-dark" /></template>
