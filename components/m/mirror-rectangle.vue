<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-bix9fdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bix9fdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mirror-rectangle" /></template>
