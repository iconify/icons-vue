<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzk332l-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzk332l-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tga" /></template>
