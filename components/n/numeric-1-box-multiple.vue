<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im1zh4btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im1zh4btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-1-box-multiple" /></template>
