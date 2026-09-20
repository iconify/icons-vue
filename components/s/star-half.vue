<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfs0h1b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfs0h1b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:star-half" /></template>
