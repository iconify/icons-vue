<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npp6aq02u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npp6aq02u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:type-italic-solid" /></template>
