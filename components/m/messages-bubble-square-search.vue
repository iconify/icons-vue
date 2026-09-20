<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu6c_ub0k.css';
import '../../css/c/c0644sbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu6c_ub0k"/><path class="c0644sbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-square-search" /></template>
