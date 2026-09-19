<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9ae9mbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9ae9mbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:outline" /></template>
