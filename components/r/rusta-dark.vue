<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_ul1fyxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_ul1fyxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rusta-dark" /></template>
