<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsq_ef9ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsq_ef9ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quote-left-fill" /></template>
