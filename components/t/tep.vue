<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pynayyb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pynayyb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:tep" /></template>
