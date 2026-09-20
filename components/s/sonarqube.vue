<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0o3l0b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0o3l0b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonarqube" /></template>
