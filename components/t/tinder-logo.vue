<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c84gzcc_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c84gzcc_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tinder-logo" /></template>
