<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrazbb12a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrazbb12a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-sleep" /></template>
