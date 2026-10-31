<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z36h-vb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z36h-vb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-grid-small-duocolor-round" /></template>
