<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edwif1blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edwif1blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:off-outline-close" /></template>
