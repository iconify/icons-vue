<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z51j4rbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z51j4rbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:military-rank-filled" /></template>
