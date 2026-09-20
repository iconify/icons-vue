<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmh4b8b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmh4b8b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:splunk" /></template>
