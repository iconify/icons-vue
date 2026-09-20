<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o147f5bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o147f5bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-left" /></template>
