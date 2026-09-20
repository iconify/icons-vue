<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ayzmbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ayzmbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-angry-filled" /></template>
