<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo88zq3co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo88zq3co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openspeedtest" /></template>
