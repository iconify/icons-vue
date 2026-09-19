<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv1r_vbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv1r_vbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tombstone" /></template>
