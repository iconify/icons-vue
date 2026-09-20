<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgy3_4bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgy3_4bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yew" /></template>
