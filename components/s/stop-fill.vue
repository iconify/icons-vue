<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c911d0bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c911d0bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stop-fill" /></template>
