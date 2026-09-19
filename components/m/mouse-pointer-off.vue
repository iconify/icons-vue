<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i27q8j8lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i27q8j8lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-pointer-off" /></template>
