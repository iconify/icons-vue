<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foa44bdgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="foa44bdgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:showpad" /></template>
