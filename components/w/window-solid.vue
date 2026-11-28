<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heb4gabhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heb4gabhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:window-solid" /></template>
