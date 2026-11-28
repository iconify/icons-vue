<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki6s-xbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki6s-xbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-2-solid" /></template>
