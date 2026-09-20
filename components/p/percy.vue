<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwnlmd5li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwnlmd5li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:percy" /></template>
