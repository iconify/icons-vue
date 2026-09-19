<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egk3f8m5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egk3f8m5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-select" /></template>
