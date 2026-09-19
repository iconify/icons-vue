<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6w1e-blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6w1e-blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-minus-filled" /></template>
