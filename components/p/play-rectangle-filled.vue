<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vws7xf1nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vws7xf1nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-rectangle-filled" /></template>
