<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t96l2flpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t96l2flpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:plane" /></template>
