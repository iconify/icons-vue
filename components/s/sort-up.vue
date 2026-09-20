<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4h4c4zzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4h4c4zzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-up" /></template>
