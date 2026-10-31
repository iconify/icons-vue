<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju2jembnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju2jembnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:siren-off" /></template>
