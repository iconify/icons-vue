<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqdd3lnje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqdd3lnje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:penpot" /></template>
