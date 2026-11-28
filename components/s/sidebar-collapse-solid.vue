<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2bbonbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2bbonbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sidebar-collapse-solid" /></template>
