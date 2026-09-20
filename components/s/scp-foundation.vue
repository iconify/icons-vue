<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo91-lb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo91-lb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scp-foundation" /></template>
