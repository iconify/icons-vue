<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ggb4u2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ggb4u2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-dashed" /></template>
