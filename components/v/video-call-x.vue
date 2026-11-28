<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2b3r1gbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2b3r1gbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-call-x" /></template>
