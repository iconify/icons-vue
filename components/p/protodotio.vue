<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvsiy_b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvsiy_b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:protodotio" /></template>
