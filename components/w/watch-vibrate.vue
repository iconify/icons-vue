<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvrty83tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvrty83tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:watch-vibrate" /></template>
