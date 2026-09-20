<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhw69qmyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhw69qmyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:pi-outline" /></template>
