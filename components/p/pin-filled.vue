<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avcg7_bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avcg7_bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pin-filled" /></template>
