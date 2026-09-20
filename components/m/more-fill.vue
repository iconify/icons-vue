<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvo-qbbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvo-qbbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:more-fill" /></template>
