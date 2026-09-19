<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6r5btlna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x6r5btlna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:nintendo-switch" /></template>
