<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v36pdtiyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v36pdtiyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:meter-fill" /></template>
