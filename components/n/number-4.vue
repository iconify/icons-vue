<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snraypi8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snraypi8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-4" /></template>
