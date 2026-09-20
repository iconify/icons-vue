<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpcxctqsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cpcxctqsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:telegram" /></template>
