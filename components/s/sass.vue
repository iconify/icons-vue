<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-t_88bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-t_88bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sass" /></template>
