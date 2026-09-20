<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k12688poe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k12688poe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:make" /></template>
