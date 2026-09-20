<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbk945l6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbk945l6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:milvus" /></template>
