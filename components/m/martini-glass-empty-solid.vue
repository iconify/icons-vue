<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdk6vevrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdk6vevrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:martini-glass-empty-solid" /></template>
