<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r99r82azc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r99r82azc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:screen-share" /></template>
