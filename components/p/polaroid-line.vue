<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbovjhb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbovjhb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:polaroid-line" /></template>
