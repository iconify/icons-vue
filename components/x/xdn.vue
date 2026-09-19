<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0jokmbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v0jokmbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xdn" /></template>
