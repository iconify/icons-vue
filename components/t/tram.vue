<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqk0ldt8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk0ldt8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tram" /></template>
