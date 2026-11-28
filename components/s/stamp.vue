<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzxhyvkgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzxhyvkgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stamp" /></template>
