<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezg2qibut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezg2qibut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spdx" /></template>
