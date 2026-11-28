<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-g_vsbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-g_vsbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thumbs-up-solid" /></template>
