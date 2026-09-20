<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwlt0zbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwlt0zbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:monument-filled" /></template>
