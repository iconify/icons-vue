<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbic-tukd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbic-tukd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pending-filled" /></template>
