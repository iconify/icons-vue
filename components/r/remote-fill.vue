<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyc9sacdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyc9sacdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:remote-fill" /></template>
