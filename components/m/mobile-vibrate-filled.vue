<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjk9j1bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjk9j1bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mobile-vibrate-filled" /></template>
