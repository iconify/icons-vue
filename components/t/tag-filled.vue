<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndo2xbcch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndo2xbcch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tag-filled" /></template>
