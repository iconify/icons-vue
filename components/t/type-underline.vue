<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3kg42pzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3kg42pzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:type-underline" /></template>
