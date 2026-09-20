<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpz6ftb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hpz6ftb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onenote-2018-light" /></template>
