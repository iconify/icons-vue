<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaw36fbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":710};
const content = `<path class="aaw36fbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:money" /></template>
