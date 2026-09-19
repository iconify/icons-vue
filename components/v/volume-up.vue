<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbzqi4cyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":24};
const content = `<path class="fbzqi4cyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:volume-up" /></template>
