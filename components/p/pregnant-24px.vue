<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3jm3bc0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3jm3bc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pregnant-24px" /></template>
