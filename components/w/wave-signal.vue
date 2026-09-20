<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfdkbab2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nfdkbab2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:wave-signal" /></template>
