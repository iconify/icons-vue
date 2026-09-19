<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0vakmb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0vakmb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:paperclip-off" /></template>
