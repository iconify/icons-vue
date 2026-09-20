<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff4d8cc3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff4d8cc3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:step" /></template>
