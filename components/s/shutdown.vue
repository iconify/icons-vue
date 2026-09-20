<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py7hu3tca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py7hu3tca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shutdown" /></template>
