<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c38x5m7rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c38x5m7rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:popsicle" /></template>
