<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u12i6ub3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u12i6ub3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rubber-stamp" /></template>
