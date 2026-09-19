<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-a5-2npd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-a5-2npd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:th-large" /></template>
