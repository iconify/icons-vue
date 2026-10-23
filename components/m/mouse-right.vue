<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uskg7un7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uskg7un7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-right" /></template>
