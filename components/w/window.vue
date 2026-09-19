<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq2h9qb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq2h9qb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:window" /></template>
