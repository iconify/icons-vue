<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-wiaqb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-wiaqb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:orthogonal-view" /></template>
