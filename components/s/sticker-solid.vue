<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz_bkbbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz_bkbbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sticker-solid" /></template>
