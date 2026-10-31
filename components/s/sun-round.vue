<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hekxj6n4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hekxj6n4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-round" /></template>
