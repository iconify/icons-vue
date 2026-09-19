<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lusqrr91b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lusqrr91b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:play-pause" /></template>
