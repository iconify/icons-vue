<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duvpq18rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":630,"height":850};
const content = `<path class="duvpq18rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:pin" /></template>
