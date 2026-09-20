<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8-f5abwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8-f5abwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-plus-inside-solid" /></template>
