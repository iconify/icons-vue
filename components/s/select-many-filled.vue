<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waxdupbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waxdupbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:select-many-filled" /></template>
