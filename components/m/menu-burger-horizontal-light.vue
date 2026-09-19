<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfx5qrwbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfx5qrwbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-horizontal-light" /></template>
