<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yur0lzbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yur0lzbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:round-sticker-fill" /></template>
