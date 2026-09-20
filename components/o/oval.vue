<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0fz66bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0fz66bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:oval" /></template>
