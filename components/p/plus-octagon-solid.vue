<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs2gjggro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs2gjggro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-octagon-solid" /></template>
