<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdxb9g3oh.css';
import '../../css/g/gb0c95-cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdxb9g3oh"/><path class="gb0c95-cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:master-card" /></template>
