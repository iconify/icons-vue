<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct4igk9uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct4igk9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:ticket-voucher" /></template>
