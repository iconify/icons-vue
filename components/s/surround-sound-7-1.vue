<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzu4d0kby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzu4d0kby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surround-sound-7-1" /></template>
