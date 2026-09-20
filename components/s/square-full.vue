<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra1_58_jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ra1_58_jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:square-full" /></template>
