<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktpt-8bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktpt-8bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paper-clock-light" /></template>
