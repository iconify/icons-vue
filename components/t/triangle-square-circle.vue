<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgtuqxbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgtuqxbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-square-circle" /></template>
