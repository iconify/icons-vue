<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f--c2tkag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f--c2tkag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mop-sparkles" /></template>
