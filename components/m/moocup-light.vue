<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxg6ho_0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uxg6ho_0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moocup-light" /></template>
