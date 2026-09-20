<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9cq85lbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9cq85lbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wheelchair-1" /></template>
