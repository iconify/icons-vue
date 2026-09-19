<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w24i2lbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w24i2lbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:video-recording" /></template>
