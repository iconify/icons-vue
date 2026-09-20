<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryt2j8s9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryt2j8s9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-top-inactive-solid" /></template>
