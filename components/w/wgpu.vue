<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyzz1lqqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyzz1lqqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wgpu" /></template>
