<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orq01ibyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orq01ibyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:svelte" /></template>
