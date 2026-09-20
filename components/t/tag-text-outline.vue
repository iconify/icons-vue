<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5e7fzb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5e7fzb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-text-outline" /></template>
