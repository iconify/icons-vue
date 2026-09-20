<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn9vxj7ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn9vxj7ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-plus" /></template>
