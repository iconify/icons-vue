<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u372c1oye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u372c1oye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vaccine-off" /></template>
