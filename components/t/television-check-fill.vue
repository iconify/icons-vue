<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8pwkeb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8pwkeb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:television-check-fill" /></template>
