<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qca3mjvib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qca3mjvib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temperature-auto" /></template>
