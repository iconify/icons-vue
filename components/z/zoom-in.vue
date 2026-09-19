<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhvh4xbwq.css';
import '../../css/f/fj4btac-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhvh4xbwq"/><path class="fj4btac-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:zoom-in" /></template>
