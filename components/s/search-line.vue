<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w307vljyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w307vljyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:search-line" /></template>
