<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8wbh2bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8wbh2bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:redo" /></template>
