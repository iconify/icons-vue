<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3kiame8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3kiame8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:video" /></template>
