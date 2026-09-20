<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg9gvxw4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9gvxw4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-location" /></template>
