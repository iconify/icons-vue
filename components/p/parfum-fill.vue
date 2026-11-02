<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp9b9bcbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp9b9bcbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parfum-fill" /></template>
