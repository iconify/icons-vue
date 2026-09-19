<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emdirgbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emdirgbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:map" /></template>
