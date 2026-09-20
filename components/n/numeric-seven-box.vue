<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odqejdbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odqejdbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-seven-box" /></template>
