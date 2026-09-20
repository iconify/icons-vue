<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1tms5bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="i1tms5bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:music" /></template>
