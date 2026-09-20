<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8lln2bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y8lln2bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pin-alt-outline" /></template>
