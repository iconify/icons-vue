<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3oq2shun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3oq2shun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paperclip-plus" /></template>
