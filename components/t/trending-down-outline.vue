<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiee_78vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiee_78vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:trending-down-outline" /></template>
