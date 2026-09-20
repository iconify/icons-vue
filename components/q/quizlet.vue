<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmvw5nbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmvw5nbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:quizlet" /></template>
