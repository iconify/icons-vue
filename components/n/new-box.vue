<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaisofb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaisofb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:new-box" /></template>
