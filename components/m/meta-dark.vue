<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agfvdyben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="agfvdyben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meta-dark" /></template>
