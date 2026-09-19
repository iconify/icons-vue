<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg7smxi4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg7smxi4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zip-01" /></template>
