<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncp4okbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncp4okbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-minus-round" /></template>
