<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry15pac0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry15pac0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-outline" /></template>
