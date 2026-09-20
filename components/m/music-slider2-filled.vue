<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loe9jibay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="loe9jibay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-slider2-filled" /></template>
