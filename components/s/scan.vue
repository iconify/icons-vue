<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3-a4gbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3-a4gbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:scan" /></template>
