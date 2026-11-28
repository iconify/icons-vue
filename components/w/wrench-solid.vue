<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1xp4e_uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1xp4e_uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wrench-solid" /></template>
