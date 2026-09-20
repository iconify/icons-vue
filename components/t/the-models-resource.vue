<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isgee_aqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isgee_aqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-models-resource" /></template>
