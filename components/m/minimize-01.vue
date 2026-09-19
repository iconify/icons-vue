<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv3rhpbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv3rhpbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:minimize-01" /></template>
