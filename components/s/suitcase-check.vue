<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3alk_bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3alk_bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:suitcase-check" /></template>
