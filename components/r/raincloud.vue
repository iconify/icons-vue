<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_7l6fcgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_7l6fcgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:raincloud" /></template>
