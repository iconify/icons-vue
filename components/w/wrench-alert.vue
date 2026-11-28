<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcqt--beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcqt--beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wrench-alert" /></template>
