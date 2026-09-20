<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuycb9bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuycb9bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wifi-2" /></template>
