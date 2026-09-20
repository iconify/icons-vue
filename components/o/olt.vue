<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afuwfjdkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afuwfjdkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:olt" /></template>
