<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owz3mac6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owz3mac6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pound-sterling" /></template>
