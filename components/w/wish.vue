<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc9gyxref.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc9gyxref"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wish" /></template>
