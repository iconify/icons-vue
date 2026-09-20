<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mitsd4d0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mitsd4d0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2018-dark" /></template>
