<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rewhuccwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rewhuccwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:star-x" /></template>
