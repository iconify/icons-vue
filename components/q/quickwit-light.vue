<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmyb9zu8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tmyb9zu8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickwit-light" /></template>
