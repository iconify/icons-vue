<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7ro04bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7ro04bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-plus-2" /></template>
