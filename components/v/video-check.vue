<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip82d1icr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip82d1icr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-check" /></template>
