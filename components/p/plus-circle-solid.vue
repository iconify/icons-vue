<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijm667k2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijm667k2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plus-circle-solid" /></template>
