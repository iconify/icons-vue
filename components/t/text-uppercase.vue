<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ondt29ssz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ondt29ssz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-uppercase" /></template>
