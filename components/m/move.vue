<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e46-h6c3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e46-h6c3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:move" /></template>
