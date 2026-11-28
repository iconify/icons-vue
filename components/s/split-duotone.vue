<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7kco0bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7kco0bwt primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:split-duotone" /></template>
