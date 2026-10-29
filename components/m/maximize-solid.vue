<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvdow2bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvdow2bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-solid" /></template>
