<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bocvvbcei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":384};
const content = `<path class="bocvvbcei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:shape" /></template>
