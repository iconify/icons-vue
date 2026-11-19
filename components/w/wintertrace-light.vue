<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3r_b-b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3r_b-b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wintertrace-light" /></template>
