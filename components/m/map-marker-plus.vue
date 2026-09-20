<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uulm_obub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uulm_obub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-marker-plus" /></template>
