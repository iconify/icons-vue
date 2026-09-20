<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikzj6qbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikzj6qbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:volume-high" /></template>
