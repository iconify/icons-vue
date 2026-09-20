<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8z1f3_sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8z1f3_sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stop-fill" /></template>
