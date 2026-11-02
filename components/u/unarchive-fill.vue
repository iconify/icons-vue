<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7a0z09jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7a0z09jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unarchive-fill" /></template>
