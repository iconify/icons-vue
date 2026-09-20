<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydkqw95qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydkqw95qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-upload-fill" /></template>
