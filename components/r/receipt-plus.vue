<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enbnuf7yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enbnuf7yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:receipt-plus" /></template>
