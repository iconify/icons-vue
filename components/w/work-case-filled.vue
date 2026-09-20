<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgz-ogbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgz-ogbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:work-case-filled" /></template>
