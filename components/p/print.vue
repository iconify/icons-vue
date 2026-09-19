<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep9p_6bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep9p_6bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:print" /></template>
