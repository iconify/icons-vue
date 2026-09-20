<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfra_acnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfra_acnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-woman-book-bold" /></template>
