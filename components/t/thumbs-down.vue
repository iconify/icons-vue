<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib0cctbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib0cctbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:thumbs-down" /></template>
