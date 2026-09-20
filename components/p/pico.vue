<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l94-5x15h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l94-5x15h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pico" /></template>
