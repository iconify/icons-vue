<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp9t_v64j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp9t_v64j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sticker-filled" /></template>
