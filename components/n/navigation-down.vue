<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbpp6qb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbpp6qb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-down" /></template>
