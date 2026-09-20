<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nng69hcoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nng69hcoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:picture-in-picture-2-line" /></template>
