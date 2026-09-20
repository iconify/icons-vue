<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lui9wgb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lui9wgb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:share-2" /></template>
