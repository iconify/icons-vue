<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_7lhvb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_7lhvb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:walker" /></template>
