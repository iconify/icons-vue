<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7mcmrbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7mcmrbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:speechless-1-filled" /></template>
