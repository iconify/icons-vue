<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vve2ttzer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vve2ttzer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sort-arrow-light" /></template>
