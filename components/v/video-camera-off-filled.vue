<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk3-2qb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk3-2qb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:video-camera-off-filled" /></template>
