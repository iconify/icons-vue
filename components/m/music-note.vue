<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0hqf1bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0hqf1bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:music-note" /></template>
