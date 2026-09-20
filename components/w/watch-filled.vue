<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moz6u8bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moz6u8bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:watch-filled" /></template>
