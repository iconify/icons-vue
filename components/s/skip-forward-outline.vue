<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4v084nuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4v084nuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:skip-forward-outline" /></template>
