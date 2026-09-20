<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4j0-p4on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="g4j0-p4on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:wrench-f" /></template>
