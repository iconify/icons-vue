<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgqkzk5ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgqkzk5ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:move-up" /></template>
