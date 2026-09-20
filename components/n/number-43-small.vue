<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re9ycvy8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re9ycvy8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-43-small" /></template>
