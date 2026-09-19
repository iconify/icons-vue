<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dksa10bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dksa10bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-right" /></template>
