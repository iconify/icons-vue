<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhpt4fbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhpt4fbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:repeat-off" /></template>
