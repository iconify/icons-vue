<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy4lr8bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sy4lr8bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-plus2" /></template>
