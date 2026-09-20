<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yase_ybcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yase_ybcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-low-sharp" /></template>
