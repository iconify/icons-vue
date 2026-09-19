<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfxuosbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfxuosbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:tools" /></template>
