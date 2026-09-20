<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaq560y5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaq560y5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-triangle" /></template>
