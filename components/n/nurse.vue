<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7z45hb6b.css';
import '../../css/s/s7g2vkbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7z45hb6b"/><path class="s7g2vkbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:nurse" /></template>
