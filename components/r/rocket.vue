<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_gz97l3s.css';
import '../../css/y/yn8-hpb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_gz97l3s"/><path class="yn8-hpb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:rocket" /></template>
