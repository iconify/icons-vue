<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h85qfccxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h85qfccxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-plus" /></template>
