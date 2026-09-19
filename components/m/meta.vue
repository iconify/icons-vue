<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp6yeibsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp6yeibsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:meta" /></template>
