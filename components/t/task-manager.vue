<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0du-8btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m0du-8btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:task-manager" /></template>
