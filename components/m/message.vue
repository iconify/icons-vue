<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut1_9hdzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut1_9hdzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:message" /></template>
