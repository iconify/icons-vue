<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k--l8mfbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k--l8mfbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:max-dark" /></template>
