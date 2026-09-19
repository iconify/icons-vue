<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kow7hrb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kow7hrb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:percentage-square-solid" /></template>
