<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8q1dggjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8q1dggjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-list" /></template>
