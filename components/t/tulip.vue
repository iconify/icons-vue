<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6gxh7bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6gxh7bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tulip" /></template>
