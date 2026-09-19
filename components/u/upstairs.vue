<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t96ugl3qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t96ugl3qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:upstairs" /></template>
