<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urlgr2eji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urlgr2eji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:programming-arrow-filled" /></template>
