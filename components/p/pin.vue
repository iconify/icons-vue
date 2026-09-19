<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9q8blfqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9q8blfqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pin" /></template>
