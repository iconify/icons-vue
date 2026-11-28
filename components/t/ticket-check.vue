<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkj9vcbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkj9vcbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ticket-check" /></template>
