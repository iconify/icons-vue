<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu-ii1brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu-ii1brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mode-embedding-filled" /></template>
