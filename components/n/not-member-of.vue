<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwu1q-4-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwu1q-4-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:not-member-of" /></template>
