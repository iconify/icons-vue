<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_8d67b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g_8d67b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:w" /></template>
