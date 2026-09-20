<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5qdc0b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n5qdc0b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:poo-storm-solid" /></template>
