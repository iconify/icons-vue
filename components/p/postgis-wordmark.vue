<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiq-kp2it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eiq-kp2it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:postgis-wordmark" /></template>
