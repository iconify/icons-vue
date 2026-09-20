<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyc75eb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyc75eb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-case-uppercase" /></template>
