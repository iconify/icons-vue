<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2fids0_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2fids0_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plus" /></template>
