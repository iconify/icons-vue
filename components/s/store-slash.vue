<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvwb37b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvwb37b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:store-slash" /></template>
