<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktl-3pzor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktl-3pzor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:repost" /></template>
