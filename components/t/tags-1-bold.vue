<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjyk13fxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjyk13fxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tags-1-bold" /></template>
