<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzn5nb1wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzn5nb1wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-bottom" /></template>
