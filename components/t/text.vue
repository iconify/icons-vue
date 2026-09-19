<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7q6z1bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7q6z1bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:text" /></template>
