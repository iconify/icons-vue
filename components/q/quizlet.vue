<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueff_ibdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueff_ibdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:quizlet" /></template>
