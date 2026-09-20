<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byc2hjbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byc2hjbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-remove" /></template>
