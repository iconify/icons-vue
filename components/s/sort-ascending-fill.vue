<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-sp1cbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-sp1cbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sort-ascending-fill" /></template>
