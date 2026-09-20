<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9-fgdbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9-fgdbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-template-24" /></template>
