<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udgaq9por.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udgaq9por"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sidebar-left2-filled" /></template>
