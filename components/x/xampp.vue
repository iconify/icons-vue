<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt4ma9bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt4ma9bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xampp" /></template>
