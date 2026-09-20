<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1vz8bvvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1vz8bvvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:switch-vertical" /></template>
