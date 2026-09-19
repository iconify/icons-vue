<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgirl4yno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="mgirl4yno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:suitcase-alt" /></template>
