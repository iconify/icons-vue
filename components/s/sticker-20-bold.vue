<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgevkmbzk.css';
import '../../css/b/bwnp5t_qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sgevkmbzk"/><path class="bwnp5t_qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticker-20-bold" /></template>
