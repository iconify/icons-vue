<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9df3ow_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9df3ow_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:peanut-off-outline" /></template>
