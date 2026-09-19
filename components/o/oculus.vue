<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhotyywae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dhotyywae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:oculus" /></template>
