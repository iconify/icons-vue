<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev4u0tl6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev4u0tl6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:virus" /></template>
