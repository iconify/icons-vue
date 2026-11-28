<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csdv1sb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csdv1sb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-gear" /></template>
