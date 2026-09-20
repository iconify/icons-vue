<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sidyi6d3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sidyi6d3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-off-filled" /></template>
