<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr1noyk3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr1noyk3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:oclc" /></template>
