<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j155pvb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j155pvb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:memory-stick" /></template>
