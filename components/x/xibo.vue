<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tppqtvgwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tppqtvgwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xibo" /></template>
