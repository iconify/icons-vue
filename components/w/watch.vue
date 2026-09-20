<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w99c1bbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w99c1bbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:watch" /></template>
