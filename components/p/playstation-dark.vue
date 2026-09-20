<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqk2x3b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqk2x3b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:playstation-dark" /></template>
