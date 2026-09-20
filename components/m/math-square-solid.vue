<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htgra2j3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htgra2j3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:math-square-solid" /></template>
