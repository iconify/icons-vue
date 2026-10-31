<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6t0d20fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6t0d20fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:star-half" /></template>
