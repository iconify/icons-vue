<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq9by0bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq9by0bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rescript" /></template>
