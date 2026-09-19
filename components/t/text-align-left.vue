<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz711pbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz711pbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:text-align-left" /></template>
