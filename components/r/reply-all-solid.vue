<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u34groiwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u34groiwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reply-all-solid" /></template>
