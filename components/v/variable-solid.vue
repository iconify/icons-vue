<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwb388bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwb388bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:variable-solid" /></template>
