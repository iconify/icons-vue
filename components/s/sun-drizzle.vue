<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azp8fbcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azp8fbcgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-drizzle" /></template>
