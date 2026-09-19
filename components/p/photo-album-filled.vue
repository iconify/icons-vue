<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp6hdkbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6hdkbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:photo-album-filled" /></template>
