<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_b9ttbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-4.5};
const content = `<path class="u_b9ttbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:plus" /></template>
