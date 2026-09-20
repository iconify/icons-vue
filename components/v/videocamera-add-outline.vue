<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiusxccnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yiusxccnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-add-outline" /></template>
