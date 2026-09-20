<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt9b5egoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt9b5egoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-top-inactive" /></template>
