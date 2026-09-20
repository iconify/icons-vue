<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xthn5fbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xthn5fbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vector-bezier" /></template>
