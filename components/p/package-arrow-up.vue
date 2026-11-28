<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhqu29b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhqu29b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-arrow-up" /></template>
