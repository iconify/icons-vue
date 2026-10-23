<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow382xozz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow382xozz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:spell-check" /></template>
