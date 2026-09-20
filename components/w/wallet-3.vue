<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w36eivbky.css';
import '../../css/i/isad52bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w36eivbky"/><path class="isad52bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wallet-3" /></template>
