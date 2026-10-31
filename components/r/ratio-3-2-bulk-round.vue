<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt3tfnmyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt3tfnmyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-3-2-bulk-round" /></template>
