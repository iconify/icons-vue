<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oytogubbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oytogubbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-align-end" /></template>
