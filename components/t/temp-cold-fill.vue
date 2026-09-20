<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueuic50-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueuic50-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:temp-cold-fill" /></template>
