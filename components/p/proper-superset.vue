<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pma34jxip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pma34jxip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:proper-superset" /></template>
