<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ee8cbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ee8cbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:vending-machine" /></template>
