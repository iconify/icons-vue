<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im2df2dro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="im2df2dro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:video-close-captioning-solid" /></template>
