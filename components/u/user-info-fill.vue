<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drq72ey7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drq72ey7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-info-fill" /></template>
