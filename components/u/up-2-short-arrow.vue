<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka-7rw9rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka-7rw9rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:up-2-short-arrow" /></template>
