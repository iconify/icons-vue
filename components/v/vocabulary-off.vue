<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsjirq5le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsjirq5le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vocabulary-off" /></template>
