<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yueg-wzbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yueg-wzbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-right-bottom" /></template>
