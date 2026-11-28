<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc3w86psn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc3w86psn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rotate-cw-solid" /></template>
