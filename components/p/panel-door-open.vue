<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybio2ac2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybio2ac2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-door-open" /></template>
