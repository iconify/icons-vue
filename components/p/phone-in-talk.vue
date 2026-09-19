<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1z3g4b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="i1z3g4b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-in-talk" /></template>
