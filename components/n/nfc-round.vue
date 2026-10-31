<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnfnllbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnfnllbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:nfc-round" /></template>
