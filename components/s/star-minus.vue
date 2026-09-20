<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db8-kccpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db8-kccpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:star-minus" /></template>
