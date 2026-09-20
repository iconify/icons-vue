<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2-cq6prt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2-cq6prt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mewe" /></template>
