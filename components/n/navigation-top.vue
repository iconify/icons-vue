<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2w2y2ajr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2w2y2ajr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-top" /></template>
