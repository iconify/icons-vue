<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9e7_umfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9e7_umfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:navigator" /></template>
