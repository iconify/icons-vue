<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4u691ylc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4u691ylc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror4" /></template>
