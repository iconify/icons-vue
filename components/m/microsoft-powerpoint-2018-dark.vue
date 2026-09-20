<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neold9btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="neold9btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-2018-dark" /></template>
