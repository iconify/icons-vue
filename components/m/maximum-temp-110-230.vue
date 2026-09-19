<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y893vacol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="y893vacol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:maximum-temp-110-230" /></template>
