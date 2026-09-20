<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsj-ypelj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsj-ypelj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:waves-horizontal" /></template>
