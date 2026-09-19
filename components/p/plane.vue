<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tluec13rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tluec13rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:plane" /></template>
