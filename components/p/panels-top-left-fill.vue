<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3q48_xry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3q48_xry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-top-left-fill" /></template>
