<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4o6dbcvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4o6dbcvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scan" /></template>
