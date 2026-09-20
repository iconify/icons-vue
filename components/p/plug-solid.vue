<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aadq953xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aadq953xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:plug-solid" /></template>
