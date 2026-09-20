<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c21ih15aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c21ih15aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star3" /></template>
