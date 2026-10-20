<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_1lh9bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_1lh9bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sticky-note" /></template>
