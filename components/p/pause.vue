<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc12bymlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc12bymlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pause" /></template>
