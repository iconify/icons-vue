<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7jqs6v7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7jqs6v7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:stat-down" /></template>
