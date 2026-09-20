<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocvuu5baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocvuu5baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text" /></template>
