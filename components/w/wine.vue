<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peommn6jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peommn6jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wine" /></template>
