<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9t_8ob2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9t_8ob2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:safe-3-line" /></template>
