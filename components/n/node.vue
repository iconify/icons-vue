<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu1rz2bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu1rz2bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:node" /></template>
