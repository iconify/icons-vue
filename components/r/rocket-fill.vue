<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijs-9ub4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijs-9ub4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:rocket-fill" /></template>
