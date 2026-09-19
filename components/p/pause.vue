<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d193zacho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d193zacho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pause" /></template>
