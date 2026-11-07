<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1dwv0bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1dwv0bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-circle-outline" /></template>
