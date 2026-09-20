<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcerrwbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcerrwbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:octopusdeploy" /></template>
