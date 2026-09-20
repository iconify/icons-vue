<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yve461b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yve461b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:prescription" /></template>
