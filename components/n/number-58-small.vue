<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs8f3nbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs8f3nbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-58-small" /></template>
