<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prbcqzb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prbcqzb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:ticket" /></template>
