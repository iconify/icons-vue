<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hom_x8bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hom_x8bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:not-equal" /></template>
