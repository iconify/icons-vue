<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_dj60b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_dj60b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-excel" /></template>
