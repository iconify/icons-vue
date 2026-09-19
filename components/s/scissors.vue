<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkv4lj3ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="vkv4lj3ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:scissors" /></template>
