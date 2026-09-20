<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q57e--beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q57e--beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:north-star" /></template>
