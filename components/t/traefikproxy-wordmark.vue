<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj588pbsy.css';
import '../../css/l/l10hz5bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mj588pbsy"/><path class="l10hz5bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:traefikproxy-wordmark" /></template>
