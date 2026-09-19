<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2qjncbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":512};
const content = `<path class="n2qjncbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tablet-mac" /></template>
