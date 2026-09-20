<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x72p28bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x72p28bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-left-bottom" /></template>
