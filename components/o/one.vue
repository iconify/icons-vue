<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_flq3hst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_flq3hst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:one" /></template>
