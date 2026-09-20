<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3c6beb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y3c6beb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mark-3" /></template>
