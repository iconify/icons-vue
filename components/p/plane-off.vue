<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f75ofabbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f75ofabbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plane-off" /></template>
