<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id2dg3ljq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id2dg3ljq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rubber-stamp-off" /></template>
