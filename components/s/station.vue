<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnr7b16vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="vnr7b16vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:station" /></template>
