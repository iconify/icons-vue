<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n39z9fd7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n39z9fd7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:overcast" /></template>
