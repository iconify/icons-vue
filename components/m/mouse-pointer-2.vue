<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtxprhl3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtxprhl3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-2" /></template>
