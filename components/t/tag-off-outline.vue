<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h39_wuqyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h39_wuqyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-off-outline" /></template>
