<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpyidubfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpyidubfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minus-outline" /></template>
