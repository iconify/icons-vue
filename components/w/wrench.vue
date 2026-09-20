<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf33gv8ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf33gv8ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wrench" /></template>
