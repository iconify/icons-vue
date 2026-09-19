<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f24x832-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f24x832-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:view-day" /></template>
