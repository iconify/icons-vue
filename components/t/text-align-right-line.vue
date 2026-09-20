<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtun522li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtun522li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:text-align-right-line" /></template>
