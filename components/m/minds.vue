<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhi-qwb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhi-qwb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:minds" /></template>
