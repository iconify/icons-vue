<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emonlbu4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emonlbu4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:volume-low-filled" /></template>
