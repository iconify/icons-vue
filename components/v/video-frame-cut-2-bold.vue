<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg6_69hzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg6_69hzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-2-bold" /></template>
