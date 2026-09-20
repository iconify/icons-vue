<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/citx28jbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="citx28jbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:startdotgg" /></template>
