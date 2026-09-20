<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi65vucqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi65vucqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:multiplier-0-5x" /></template>
