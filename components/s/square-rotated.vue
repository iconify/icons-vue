<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unx6_330e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unx6_330e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rotated" /></template>
