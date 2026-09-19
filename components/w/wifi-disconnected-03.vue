<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9cdxv7cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9cdxv7cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-disconnected-03" /></template>
