<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji8-djbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji8-djbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:viadeo" /></template>
