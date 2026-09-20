<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjvjlwbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjvjlwbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rotate-clockwise-2" /></template>
