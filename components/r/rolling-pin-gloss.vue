<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt8yg5lzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt8yg5lzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rolling-pin-gloss" /></template>
