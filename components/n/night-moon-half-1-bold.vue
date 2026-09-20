<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcb9oqsfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcb9oqsfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:night-moon-half-1-bold" /></template>
