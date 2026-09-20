<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjtaybc8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjtaybc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:space-ship-2-fill" /></template>
