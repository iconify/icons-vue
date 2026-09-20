<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0v2foqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un0v2foqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wall-sconce-variant" /></template>
