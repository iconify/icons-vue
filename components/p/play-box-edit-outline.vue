<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx3dfzuvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx3dfzuvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box-edit-outline" /></template>
