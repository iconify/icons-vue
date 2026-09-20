<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py6junblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py6junblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tornado" /></template>
