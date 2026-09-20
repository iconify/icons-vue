<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx7qkkual.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx7qkkual"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scissors-horizontal" /></template>
