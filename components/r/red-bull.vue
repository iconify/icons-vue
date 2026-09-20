<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge8fmxbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge8fmxbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:red-bull" /></template>
