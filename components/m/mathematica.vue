<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg3bin-au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sg3bin-au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mathematica" /></template>
