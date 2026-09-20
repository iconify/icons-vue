<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svo0q69nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svo0q69nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-down" /></template>
