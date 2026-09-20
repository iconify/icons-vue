<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p88ps52_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p88ps52_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:subdirectory-arrow-right" /></template>
