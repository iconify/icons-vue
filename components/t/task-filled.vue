<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgvy4titi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgvy4titi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:task-filled" /></template>
