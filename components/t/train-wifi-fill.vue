<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqdjhp2zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqdjhp2zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:train-wifi-fill" /></template>
