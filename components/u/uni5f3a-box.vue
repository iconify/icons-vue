<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdzm7zkpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wdzm7zkpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni5f3a-box" /></template>
