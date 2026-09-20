<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo2-bs55y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo2-bs55y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-eye" /></template>
