<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b69k4tsij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b69k4tsij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mtd" /></template>
