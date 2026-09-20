<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yclwaq1he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yclwaq1he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:polaroid-fill" /></template>
