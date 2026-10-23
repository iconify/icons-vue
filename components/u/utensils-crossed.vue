<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cioe-sbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cioe-sbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:utensils-crossed" /></template>
