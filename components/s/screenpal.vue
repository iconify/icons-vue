<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmuw75duc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmuw75duc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:screenpal" /></template>
