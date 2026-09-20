<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wroykqb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wroykqb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-forward-bold" /></template>
