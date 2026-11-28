<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8mcy1yex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8mcy1yex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:syringe-solid" /></template>
