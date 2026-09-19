<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfqu-9b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mfqu-9b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:origin" /></template>
