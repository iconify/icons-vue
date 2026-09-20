<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fywxaebkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="fywxaebkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:restriction-shield" /></template>
