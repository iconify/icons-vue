<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4sd0g1go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="k4sd0g1go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:test-tube-alt" /></template>
