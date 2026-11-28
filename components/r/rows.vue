<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qelm-abfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qelm-abfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rows" /></template>
