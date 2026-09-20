<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ekq2blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v5ekq2blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:visualbasic" /></template>
