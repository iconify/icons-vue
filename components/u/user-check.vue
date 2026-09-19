<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks8-j5qct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks8-j5qct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:user-check" /></template>
