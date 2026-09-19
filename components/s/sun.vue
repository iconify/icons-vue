<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh-b04byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh-b04byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sun" /></template>
