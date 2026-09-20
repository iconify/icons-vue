<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukufmvbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukufmvbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:polygon-line" /></template>
