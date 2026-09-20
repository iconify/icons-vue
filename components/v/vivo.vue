<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7wy442bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7wy442bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vivo" /></template>
