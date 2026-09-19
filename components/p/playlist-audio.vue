<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yllu2lzhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="yllu2lzhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:playlist-audio" /></template>
