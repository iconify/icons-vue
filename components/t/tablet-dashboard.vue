<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bubjxie-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bubjxie-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tablet-dashboard" /></template>
