<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3qet9wal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="u3qet9wal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:trending-down" /></template>
