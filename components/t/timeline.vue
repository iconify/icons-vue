<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlqrdgb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlqrdgb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:timeline" /></template>
