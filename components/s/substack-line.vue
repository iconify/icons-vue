<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okku99b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okku99b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:substack-line" /></template>
