<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bezqb2i-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bezqb2i-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scylladb" /></template>
