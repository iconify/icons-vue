<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2c24ph4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2c24ph4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-appear" /></template>
