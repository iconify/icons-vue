<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyiyvlb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyiyvlb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-16-small" /></template>
