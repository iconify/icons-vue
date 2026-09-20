<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnq9-21ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnq9-21ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-search" /></template>
