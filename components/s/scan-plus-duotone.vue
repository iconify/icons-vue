<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq-k3lbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary sq-k3lbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-plus-duotone" /></template>
