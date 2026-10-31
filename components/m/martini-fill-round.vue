<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3dt8sb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3dt8sb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:martini-fill-round" /></template>
