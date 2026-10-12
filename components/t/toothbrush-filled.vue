<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7yw6gb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7yw6gb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toothbrush-filled" /></template>
