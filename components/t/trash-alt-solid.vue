<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrhf55bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrhf55bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trash-alt-solid" /></template>
