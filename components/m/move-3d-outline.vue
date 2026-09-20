<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqkdk3e9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqkdk3e9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-3d-outline" /></template>
