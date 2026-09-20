<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrrsb2b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrrsb2b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sina-weibo" /></template>
