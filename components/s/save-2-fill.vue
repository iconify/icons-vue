<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_wz2g67s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_wz2g67s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:save-2-fill" /></template>
