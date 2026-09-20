<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px-gk6trz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px-gk6trz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:paw" /></template>
