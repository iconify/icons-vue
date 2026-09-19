<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7nc4kadu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7nc4kadu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:stairs-down-person" /></template>
