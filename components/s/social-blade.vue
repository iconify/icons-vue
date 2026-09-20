<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj0bkvovd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj0bkvovd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:social-blade" /></template>
