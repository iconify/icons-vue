<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gphtcn8kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gphtcn8kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tally-5" /></template>
