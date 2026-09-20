<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj3cigb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj3cigb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scale" /></template>
