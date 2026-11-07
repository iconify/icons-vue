<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k66ipdb2y.css';
import '../../css/u/u806m8xap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k66ipdb2y"/><path class="u806m8xap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-pause-bold" /></template>
