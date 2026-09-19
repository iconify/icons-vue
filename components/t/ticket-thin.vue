<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt33bw9wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt33bw9wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:ticket-thin" /></template>
