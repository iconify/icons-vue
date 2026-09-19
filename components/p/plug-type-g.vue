<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmy4nqiui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmy4nqiui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:plug-type-g" /></template>
