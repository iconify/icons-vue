<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hreo-frwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hreo-frwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:member-of" /></template>
