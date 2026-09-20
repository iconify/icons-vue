<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/supehpqgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="supehpqgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-360" /></template>
