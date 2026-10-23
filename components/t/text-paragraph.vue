<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot_58-5rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot_58-5rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-paragraph" /></template>
