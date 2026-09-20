<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh9r02b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9r02b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rollerblade-off" /></template>
